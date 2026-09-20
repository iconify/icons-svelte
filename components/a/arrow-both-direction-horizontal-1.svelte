<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ychnccbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ychnccbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-both-direction-horizontal-1" {...props}></Icon>
