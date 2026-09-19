<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iptqevhoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iptqevhoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:list-tree" {...props}></Icon>
