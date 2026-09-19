<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hfq8jpu7i.css';
import '../../css/w/wy2n5sbyh.css';
import '../../css/w/wekf8bf4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="hfq8jpu7i"/><path class="wy2n5sbyh"/><path class="wekf8bf4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:pensive-face-light" {...props}></Icon>
