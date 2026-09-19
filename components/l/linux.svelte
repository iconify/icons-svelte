<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bav46-0mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bav46-0mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:linux" {...props}></Icon>
