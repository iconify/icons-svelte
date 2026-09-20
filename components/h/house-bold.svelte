<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a2kliubwi.css';
import '../../css/n/n7_idhb2y.css';
import '../../css/g/gri8csbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2kliubwi"/><path clip-rule="evenodd" class="n7_idhb2y"/><path clip-rule="evenodd" class="gri8csbwd"/><path clip-rule="evenodd" class="n7_idhb2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:house-bold" {...props}></Icon>
