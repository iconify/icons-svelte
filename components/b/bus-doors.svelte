<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj-sz3bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dj-sz3bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bus-doors" {...props}></Icon>
