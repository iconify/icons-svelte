<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozf1p_y8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozf1p_y8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-golem" {...props}></Icon>
