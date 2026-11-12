<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiowh3tts.css';
import '../../css/f/flsxa_bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fiowh3tts"/><path class="flsxa_bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-forge" {...props}></Icon>
