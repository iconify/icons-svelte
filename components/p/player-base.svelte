<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp2mo1bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gp2mo1bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:player-base" {...props}></Icon>
