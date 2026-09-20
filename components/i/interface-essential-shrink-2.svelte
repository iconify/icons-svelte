<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhty85bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vhty85bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-shrink-2" {...props}></Icon>
