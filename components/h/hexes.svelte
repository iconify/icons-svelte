<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2v73ib3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2v73ib3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hexes" {...props}></Icon>
