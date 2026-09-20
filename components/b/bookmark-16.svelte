<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe7c8fl3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qe7c8fl3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-16" {...props}></Icon>
