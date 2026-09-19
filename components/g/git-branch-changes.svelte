<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zvkk_vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e8zvkk_vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-branch-changes" {...props}></Icon>
