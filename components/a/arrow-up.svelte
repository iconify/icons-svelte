<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbnufl6zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tbnufl6zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-up" {...props}></Icon>
