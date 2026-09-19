<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io2nejb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="io2nejb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egg-clutch" {...props}></Icon>
