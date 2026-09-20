<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_wh4bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c3_wh4bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-mars" {...props}></Icon>
