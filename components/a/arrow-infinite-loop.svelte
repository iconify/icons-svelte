<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrs3rsb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wrs3rsb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-infinite-loop" {...props}></Icon>
