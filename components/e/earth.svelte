<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlsz80bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tlsz80bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:earth" {...props}></Icon>
