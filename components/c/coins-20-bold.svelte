<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlxpyqbgk.css';
import '../../css/u/umey9qmui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vlxpyqbgk"/><path class="umey9qmui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coins-20-bold" {...props}></Icon>
