<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucwpi1bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ucwpi1bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:line-horizontal-3-decrease" {...props}></Icon>
