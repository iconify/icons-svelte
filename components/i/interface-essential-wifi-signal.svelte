<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e49dumbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e49dumbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-wifi-signal" {...props}></Icon>
