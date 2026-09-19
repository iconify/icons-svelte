<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv3vtfbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mv3vtfbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:old-microphone" {...props}></Icon>
