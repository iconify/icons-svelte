<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvnvnzbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yvnvnzbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-download" {...props}></Icon>
