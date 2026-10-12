<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbgf1vj4o.css';
import '../../css/l/ldkcw25ft.css';
import '../../css/j/jv0fgj_2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sbgf1vj4o"/><path class="ldkcw25ft"/><path class="jv0fgj_2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blood-drop-20-bold" {...props}></Icon>
