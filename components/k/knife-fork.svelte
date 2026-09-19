<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6k88_b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6k88_b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:knife-fork" {...props}></Icon>
