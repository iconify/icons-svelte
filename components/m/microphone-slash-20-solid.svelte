<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt4unsb2t.css';
import '../../css/f/fn009esdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yt4unsb2t"/><path class="fn009esdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:microphone-slash-20-solid" {...props}></Icon>
