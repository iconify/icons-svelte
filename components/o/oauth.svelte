<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1wq2lbyq.css';
import '../../css/x/xwnryb42j.css';
import '../../css/s/sh--qnbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y1wq2lbyq"/><path class="xwnryb42j"/><path class="sh--qnbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:oauth" {...props}></Icon>
