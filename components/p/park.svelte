<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm4j6-dsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xm4j6-dsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:park" {...props}></Icon>
