<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5gpb-b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x5gpb-b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:rename" {...props}></Icon>
