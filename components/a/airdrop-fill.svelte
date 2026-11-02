<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f30f44sse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f30f44sse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airdrop-fill" {...props}></Icon>
