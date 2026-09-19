<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfgvi2btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfgvi2btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:periscope" {...props}></Icon>
