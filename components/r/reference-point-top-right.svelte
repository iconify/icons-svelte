<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kljlrcurh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kljlrcurh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reference-point-top-right" {...props}></Icon>
