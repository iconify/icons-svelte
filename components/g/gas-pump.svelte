<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5x9eib1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5x9eib1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:gas-pump" {...props}></Icon>
