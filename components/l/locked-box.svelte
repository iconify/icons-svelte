<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlik1cyno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rlik1cyno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:locked-box" {...props}></Icon>
