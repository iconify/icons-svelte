<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk1oa_q5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nk1oa_q5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-sidebar-left-off" {...props}></Icon>
