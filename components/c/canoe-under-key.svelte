<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/who-i1bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="who-i1bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-under-key" {...props}></Icon>
