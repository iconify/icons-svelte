<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th81w-wav.css';
import '../../css/w/wvtn6fmsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="th81w-wav"/><path class="wvtn6fmsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opengist" {...props}></Icon>
