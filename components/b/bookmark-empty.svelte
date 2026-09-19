<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf1l_yb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wf1l_yb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:bookmark-empty" {...props}></Icon>
