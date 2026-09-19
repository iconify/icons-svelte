<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfbxyub8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cfbxyub8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:concentration-orb" {...props}></Icon>
