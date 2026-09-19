<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp3y8bb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp3y8bb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-gate" {...props}></Icon>
