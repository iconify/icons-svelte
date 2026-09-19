<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdum_g-ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdum_g-ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pirate-coat" {...props}></Icon>
