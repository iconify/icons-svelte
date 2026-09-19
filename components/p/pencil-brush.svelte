<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7fn9yb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y7fn9yb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pencil-brush" {...props}></Icon>
