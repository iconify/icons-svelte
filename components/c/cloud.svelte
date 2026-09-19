<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6m-1wb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6m-1wb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cloud" {...props}></Icon>
