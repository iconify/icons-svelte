<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu9hrubhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zu9hrubhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bell-fill-20" {...props}></Icon>
