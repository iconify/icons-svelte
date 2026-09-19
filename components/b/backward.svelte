<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0dc-4v8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="d0dc-4v8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:backward" {...props}></Icon>
