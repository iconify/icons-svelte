<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov_j_ngpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ov_j_ngpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-id-voice-1-identification-secure-id-soundwave-sound-voice-security" {...props}></Icon>
