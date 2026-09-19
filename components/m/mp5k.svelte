<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft6uvzk5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ft6uvzk5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mp5k" {...props}></Icon>
