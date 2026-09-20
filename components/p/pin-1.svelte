<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjukrxb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjukrxb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:pin-1" {...props}></Icon>
