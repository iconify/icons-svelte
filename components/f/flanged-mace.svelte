<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y94-w7z3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y94-w7z3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flanged-mace" {...props}></Icon>
