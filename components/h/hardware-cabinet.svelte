<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0jkzi04p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0jkzi04p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hardware-cabinet" {...props}></Icon>
