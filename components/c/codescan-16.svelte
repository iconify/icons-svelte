<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kcy-bcr.css';
import '../../css/u/uqoc3xb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r3kcy-bcr"/><path class="uqoc3xb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codescan-16" {...props}></Icon>
