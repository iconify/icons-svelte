<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-5nnccpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h-5nnccpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:dashboard" {...props}></Icon>
