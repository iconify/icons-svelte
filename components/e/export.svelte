<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx1f7dbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vx1f7dbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:export" {...props}></Icon>
