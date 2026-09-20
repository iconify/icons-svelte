<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb8bgqbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lb8bgqbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hand-dropping-circles-into-container" {...props}></Icon>
