<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj465u-3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bj465u-3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-sidebar-right-off" {...props}></Icon>
