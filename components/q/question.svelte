<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytkl7iroe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ytkl7iroe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:question" {...props}></Icon>
