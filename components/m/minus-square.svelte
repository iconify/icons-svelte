<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gewabquhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gewabquhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:minus-square" {...props}></Icon>
