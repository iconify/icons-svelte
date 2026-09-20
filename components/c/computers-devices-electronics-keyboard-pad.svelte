<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5n06o36f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5n06o36f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-keyboard-pad" {...props}></Icon>
