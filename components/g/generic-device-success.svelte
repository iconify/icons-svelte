<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e552mfb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e552mfb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-success" {...props}></Icon>
