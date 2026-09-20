<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7v1j5lau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n7v1j5lau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:move-layer-down" {...props}></Icon>
