<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctf8m1brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ctf8m1brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:magnet" {...props}></Icon>
