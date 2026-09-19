<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2qndjqkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2qndjqkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:centaur" {...props}></Icon>
