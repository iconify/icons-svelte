<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l43bgpbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l43bgpbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:djinn" {...props}></Icon>
