<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-5pfkb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="d-5pfkb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:circle-arrow-up" {...props}></Icon>
