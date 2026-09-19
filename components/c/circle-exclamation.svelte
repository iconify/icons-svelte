<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zigurz_7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zigurz_7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-exclamation" {...props}></Icon>
