<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywile0box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ywile0box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:comment-discussion-sparkle" {...props}></Icon>
