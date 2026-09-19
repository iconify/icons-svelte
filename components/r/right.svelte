<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvn6qn9gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rvn6qn9gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:right" {...props}></Icon>
