<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwiwx_jwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwiwx_jwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airpod-03" {...props}></Icon>
