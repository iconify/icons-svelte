<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wcaxpabce.css';
import '../../css/u/uowcfd4jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="wcaxpabce"/><path class="uowcfd4jh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:alarm-solid" {...props}></Icon>
