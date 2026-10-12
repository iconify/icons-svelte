<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv8044bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iv8044bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eraser-stroke-20" {...props}></Icon>
