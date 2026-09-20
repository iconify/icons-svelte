<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2jwt4bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2jwt4bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-microphone-voice-search-logo-block" {...props}></Icon>
