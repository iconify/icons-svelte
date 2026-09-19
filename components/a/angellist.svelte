<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irbh--b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1792};
const content = `<path class="irbh--b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angellist" {...props}></Icon>
