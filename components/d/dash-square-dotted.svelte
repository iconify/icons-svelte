<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqd10_6oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aqd10_6oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dash-square-dotted" {...props}></Icon>
