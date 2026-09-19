<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m5ap_-bph.css';
import '../../css/z/zg3xzp7wr.css';
import '../../css/z/z8ulehbux.css';
import '../../css/e/eoihjuteu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m5ap_-bph"/><path clip-rule="evenodd" class="zg3xzp7wr"/><path class="z8ulehbux"/><path class="eoihjuteu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:angry-outline-24px" {...props}></Icon>
