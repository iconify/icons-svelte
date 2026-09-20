<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-wrpab9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-wrpab9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fire-off" {...props}></Icon>
