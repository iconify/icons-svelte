<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykp9hft_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ykp9hft_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:minimize-stroke-16" {...props}></Icon>
