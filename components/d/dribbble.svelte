<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q12e4xb1q.css';
import '../../css/w/wcs4pjr-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="q12e4xb1q"/><path class="wcs4pjr-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:dribbble" {...props}></Icon>
