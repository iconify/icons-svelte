<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnrsqqwlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fnrsqqwlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:deno-light" {...props}></Icon>
