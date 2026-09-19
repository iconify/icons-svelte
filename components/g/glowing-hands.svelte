<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy8-t-bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wy8-t-bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:glowing-hands" {...props}></Icon>
