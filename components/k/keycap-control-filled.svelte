<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-ek5q7td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y-ek5q7td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-control-filled" {...props}></Icon>
