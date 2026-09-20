<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1dgdy9az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="t1dgdy9az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project" {...props}></Icon>
