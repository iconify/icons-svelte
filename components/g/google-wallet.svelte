<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v69s4zcsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v69s4zcsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:google-wallet" {...props}></Icon>
