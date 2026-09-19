<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3xgh4b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w3xgh4b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-arrow-down" {...props}></Icon>
