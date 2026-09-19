<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik9ampb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ik9ampb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:list" {...props}></Icon>
