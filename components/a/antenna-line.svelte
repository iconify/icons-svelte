<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmxo0ve4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmxo0ve4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:antenna-line" {...props}></Icon>
