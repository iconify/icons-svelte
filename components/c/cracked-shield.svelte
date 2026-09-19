<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l896scb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l896scb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cracked-shield" {...props}></Icon>
