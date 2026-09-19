<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trvxt9qye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="trvxt9qye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:question-lg" {...props}></Icon>
