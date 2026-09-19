<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpsmi2bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpsmi2bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:conqueror" {...props}></Icon>
