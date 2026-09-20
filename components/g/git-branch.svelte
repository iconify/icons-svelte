<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_1_-xmhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="s_1_-xmhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-branch" {...props}></Icon>
