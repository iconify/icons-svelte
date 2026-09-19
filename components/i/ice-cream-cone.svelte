<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghpm_5bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghpm_5bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-cream-cone" {...props}></Icon>
