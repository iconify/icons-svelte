<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2d_w6b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="z2d_w6b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:quote-right" {...props}></Icon>
