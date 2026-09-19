<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmjju991p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmjju991p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crowned-skull" {...props}></Icon>
