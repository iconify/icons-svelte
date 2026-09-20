<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj20fccvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yj20fccvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-ai-16" {...props}></Icon>
