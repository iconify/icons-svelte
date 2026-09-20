<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8x1wijgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="y8x1wijgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bridge" {...props}></Icon>
