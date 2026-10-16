<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itjermisk.css';
import '../../css/x/xu0oo2s1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itjermisk"/><path class="xu0oo2s1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-compressor-20-bold" {...props}></Icon>
