<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0hp5z1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lc0hp5z1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-connected" {...props}></Icon>
