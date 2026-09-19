<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiue2_bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fiue2_bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:digital-trace" {...props}></Icon>
