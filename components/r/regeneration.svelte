<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdc22dbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cdc22dbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:regeneration" {...props}></Icon>
