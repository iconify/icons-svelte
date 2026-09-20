<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umm606kxf.css';
import '../../css/f/fbm1ezbyh.css';
import '../../css/g/g6cp-sb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<g class="umm606kxf"><path class="fbm1ezbyh"/><path class="g6cp-sb3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-stickies-color:help" {...props}></Icon>
