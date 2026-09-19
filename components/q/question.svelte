<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3hs2nbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j3hs2nbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:question" {...props}></Icon>
