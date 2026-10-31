<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snlsb6x6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snlsb6x6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-sparkle-round" {...props}></Icon>
