<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lceo2ybkv.css';
import '../../css/h/hkb4kmbmc.css';
import '../../css/x/xrz9d4b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lceo2ybkv"/><path class="hkb4kmbmc"/><path class="xrz9d4b_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:compass" {...props}></Icon>
