<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfh0mccvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="bfh0mccvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:expand" {...props}></Icon>
