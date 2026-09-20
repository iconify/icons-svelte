<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjfxb6cvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjfxb6cvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:item-details" {...props}></Icon>
