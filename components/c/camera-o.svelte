<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w95bdymzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w95bdymzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:camera-o" {...props}></Icon>
