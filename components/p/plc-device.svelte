<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8l78ubrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="l8l78ubrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plc-device" {...props}></Icon>
