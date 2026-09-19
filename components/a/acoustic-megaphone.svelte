<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q74a_vbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q74a_vbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:acoustic-megaphone" {...props}></Icon>
