<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brruq5e5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="brruq5e5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-16" {...props}></Icon>
