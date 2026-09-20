<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_wcu9bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d_wcu9bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cursor-16" {...props}></Icon>
