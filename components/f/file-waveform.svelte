<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt9lf65_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yt9lf65_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-waveform" {...props}></Icon>
