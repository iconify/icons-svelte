<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciqmaqp1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ciqmaqp1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:pencil-alt" {...props}></Icon>
