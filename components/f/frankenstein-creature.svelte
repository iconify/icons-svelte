<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8dbvjb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8dbvjb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frankenstein-creature" {...props}></Icon>
