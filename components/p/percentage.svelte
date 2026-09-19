<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb1856a_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jb1856a_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:percentage" {...props}></Icon>
