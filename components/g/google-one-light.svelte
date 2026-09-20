<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj2hjiqls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hj2hjiqls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-one-light" {...props}></Icon>
