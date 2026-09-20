<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veig2p99j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veig2p99j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mastercard-line" {...props}></Icon>
