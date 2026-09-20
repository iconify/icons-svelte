<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs-u90x8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vs-u90x8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pen" {...props}></Icon>
