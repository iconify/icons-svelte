<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulq7grbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ulq7grbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mic-filled" {...props}></Icon>
