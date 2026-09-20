<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1j10obcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1j10obcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:operating-system" {...props}></Icon>
