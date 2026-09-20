<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqnnh8bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sqnnh8bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:applications" {...props}></Icon>
