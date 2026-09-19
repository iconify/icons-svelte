<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg_x3yb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xg_x3yb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calendar" {...props}></Icon>
