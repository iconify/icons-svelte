<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usb8k9bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="usb8k9bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:music" {...props}></Icon>
