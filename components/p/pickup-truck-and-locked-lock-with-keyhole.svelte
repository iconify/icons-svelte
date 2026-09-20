<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vivaadb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vivaadb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-and-locked-lock-with-keyhole" {...props}></Icon>
