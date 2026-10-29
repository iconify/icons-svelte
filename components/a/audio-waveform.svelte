<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wndgu8_xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wndgu8_xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:audio-waveform" {...props}></Icon>
