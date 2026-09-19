<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew63x3ajk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ew63x3ajk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:glide-g" {...props}></Icon>
