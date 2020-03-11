# hello-world
just other repository
#define DMA_DIR_PeripheralDST              ((uint32_t)0x00000010)  //从寄存器读
#define DMA_DIR_PeripheralSRC              ((uint32_t)0x00000000)  //从外设读
#define IS_DMA_DIR(DIR) (((DIR) == DMA_DIR_PeripheralDST) || \
                         ((DIR) == DMA_DIR_PeripheralSRC))
