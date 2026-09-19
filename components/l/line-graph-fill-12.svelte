<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi-jphbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vi-jphbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:line-graph-fill-12" {...props}></Icon>
