<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj1h_n8dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj1h_n8dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:deshret-red-crown" {...props}></Icon>
