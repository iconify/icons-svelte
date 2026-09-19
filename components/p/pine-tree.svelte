<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cectm2b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cectm2b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pine-tree" {...props}></Icon>
