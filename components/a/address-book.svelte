<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj8kg5b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bj8kg5b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:address-book" {...props}></Icon>
