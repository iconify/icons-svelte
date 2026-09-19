<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixv2spbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixv2spbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:piggy-bank" {...props}></Icon>
