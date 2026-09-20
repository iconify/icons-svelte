<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-lfmccxy.css';
import '../../css/v/v2gr9gvbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i-lfmccxy"/><path class="v2gr9gvbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-locked-16" {...props}></Icon>
