<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_iucachl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_iucachl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:audio-waveform" {...props}></Icon>
