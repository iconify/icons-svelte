<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t80g4uv5w.css';
import '../../css/x/xtau0h03z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t80g4uv5w"/><path class="xtau0h03z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-20-bold" {...props}></Icon>
