<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h69ttsb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h69ttsb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-voicemail" {...props}></Icon>
