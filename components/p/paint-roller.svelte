<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjxm42wfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjxm42wfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paint-roller" {...props}></Icon>
