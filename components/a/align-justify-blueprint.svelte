<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/atlcdwcje.css';
import '../../css/m/mhdr543mh.css';
import '../../css/l/liv-aobwc.css';
import '../../css/r/r6gbs3bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="atlcdwcje wm-deco"/><path class="mhdr543mh wm-deco"/><path class="liv-aobwc"/><path class="r6gbs3bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-justify-blueprint" {...props}></Icon>
