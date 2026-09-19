<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1uf30h9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1uf30h9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chest-armor" {...props}></Icon>
