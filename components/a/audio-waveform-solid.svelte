<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6mo-8bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6mo-8bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:audio-waveform-solid" {...props}></Icon>
