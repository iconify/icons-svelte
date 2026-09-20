<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfb6i5b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jfb6i5b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:roadmap" {...props}></Icon>
