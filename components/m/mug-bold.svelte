<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cf4va2ows.css';
import '../../css/r/r7wajpbsm.css';
import '../../css/y/yj0entbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cf4va2ows"/><path class="r7wajpbsm"/><path class="yj0entbhd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mug-bold" {...props}></Icon>
