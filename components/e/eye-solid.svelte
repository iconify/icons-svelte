<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/guewfbcxi.css';
import '../../css/z/zdjx_zbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="guewfbcxi"/><path clip-rule="evenodd" class="zdjx_zbet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-solid" {...props}></Icon>
