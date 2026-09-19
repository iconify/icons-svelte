<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbhgw8bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cbhgw8bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-alt-small" {...props}></Icon>
