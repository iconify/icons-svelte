<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpm_1gptr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wpm_1gptr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-discussion-16" {...props}></Icon>
