<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt_e7zb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rt_e7zb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:paintcan" {...props}></Icon>
