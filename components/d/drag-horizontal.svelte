<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nla6sw03w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nla6sw03w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drag-horizontal" {...props}></Icon>
