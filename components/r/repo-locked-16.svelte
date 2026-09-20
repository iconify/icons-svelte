<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl4-efmll.css';
import '../../css/u/ux165acwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rl4-efmll"/><path class="ux165acwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-locked-16" {...props}></Icon>
