<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2cyrvb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2cyrvb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hook-swords" {...props}></Icon>
