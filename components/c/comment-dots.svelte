<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-0w41hfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-0w41hfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:comment-dots" {...props}></Icon>
