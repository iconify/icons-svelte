<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqurnnynq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bqurnnynq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:moon" {...props}></Icon>
