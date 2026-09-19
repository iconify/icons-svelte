<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cza86x5tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cza86x5tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:parmecia" {...props}></Icon>
