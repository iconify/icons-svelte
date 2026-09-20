<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqy5gdbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqy5gdbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-connected" {...props}></Icon>
