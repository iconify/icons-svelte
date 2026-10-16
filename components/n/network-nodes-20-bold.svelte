<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhedj2bhl.css';
import '../../css/h/h-nm0vb_t.css';
import '../../css/i/ikay0tyrx.css';
import '../../css/j/jt5y90bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dhedj2bhl"/><path class="h-nm0vb_t"/><path class="ikay0tyrx"/><path class="jt5y90bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:network-nodes-20-bold" {...props}></Icon>
