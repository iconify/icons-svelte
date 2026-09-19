<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmgvtbbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wmgvtbbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dial-padlock" {...props}></Icon>
