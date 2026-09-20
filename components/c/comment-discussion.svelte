<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m34w601zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m34w601zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-discussion" {...props}></Icon>
