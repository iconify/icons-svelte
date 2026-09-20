<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqmr_mb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqmr_mb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ear-waveform-fill" {...props}></Icon>
