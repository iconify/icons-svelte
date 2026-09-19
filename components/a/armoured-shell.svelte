<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9_o2-3ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9_o2-3ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:armoured-shell" {...props}></Icon>
