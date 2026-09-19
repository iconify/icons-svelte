<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b55h97b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b55h97b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plesiosaurus" {...props}></Icon>
