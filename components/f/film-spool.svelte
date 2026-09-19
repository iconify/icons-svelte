<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo_akvmhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fo_akvmhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:film-spool" {...props}></Icon>
