<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bla2ybb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bla2ybb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-consulting-advantage-agent" {...props}></Icon>
