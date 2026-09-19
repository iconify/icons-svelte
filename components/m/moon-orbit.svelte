<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp_tt3b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jp_tt3b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:moon-orbit" {...props}></Icon>
