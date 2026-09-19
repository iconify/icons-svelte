<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_37f0brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i_37f0brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:night-sleep" {...props}></Icon>
