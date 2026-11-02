<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxai5t9tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxai5t9tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:audio-waveform-line" {...props}></Icon>
