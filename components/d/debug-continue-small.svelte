<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5mp5wb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z5mp5wb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-continue-small" {...props}></Icon>
