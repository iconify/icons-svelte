<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul9m5ac3g.css';
import '../../css/j/j26snyixz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ul9m5ac3g"/><path class="j26snyixz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:funnel-rtl" {...props}></Icon>
