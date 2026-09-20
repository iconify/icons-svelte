<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w86kp8b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w86kp8b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:piano-16" {...props}></Icon>
