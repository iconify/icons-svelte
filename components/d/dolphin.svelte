<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayu2mebcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ayu2mebcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dolphin" {...props}></Icon>
