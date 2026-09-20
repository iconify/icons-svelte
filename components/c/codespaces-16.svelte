<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxe-vkb4m.css';
import '../../css/v/vnwywmtwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mxe-vkb4m"/><path class="vnwywmtwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codespaces-16" {...props}></Icon>
