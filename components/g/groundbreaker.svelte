<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpn07kbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpn07kbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:groundbreaker" {...props}></Icon>
