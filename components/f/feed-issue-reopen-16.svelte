<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsk7q2blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="tsk7q2blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-issue-reopen-16" {...props}></Icon>
