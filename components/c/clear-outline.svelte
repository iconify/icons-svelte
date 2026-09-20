<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82xngbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j82xngbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:clear-outline" {...props}></Icon>
