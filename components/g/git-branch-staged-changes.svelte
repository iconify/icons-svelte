<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggx28b43y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ggx28b43y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-branch-staged-changes" {...props}></Icon>
