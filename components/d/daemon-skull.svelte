<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isq8ce6ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isq8ce6ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:daemon-skull" {...props}></Icon>
