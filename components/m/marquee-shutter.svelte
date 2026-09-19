<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyyqi6bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyyqi6bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:marquee-shutter" {...props}></Icon>
