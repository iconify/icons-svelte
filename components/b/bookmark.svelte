<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr9y6zxld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zr9y6zxld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:bookmark" {...props}></Icon>
