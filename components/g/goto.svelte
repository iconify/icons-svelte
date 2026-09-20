<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkxodebuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkxodebuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:goto" {...props}></Icon>
