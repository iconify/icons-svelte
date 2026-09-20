<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly8u96qqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ly8u96qqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-discussion-16" {...props}></Icon>
