<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jknpy-b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jknpy-b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-issue-closed-16" {...props}></Icon>
