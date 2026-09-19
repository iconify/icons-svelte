<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj5hqvbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="dj5hqvbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:print" {...props}></Icon>
