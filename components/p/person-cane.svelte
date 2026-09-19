<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp1vynl4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yp1vynl4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-cane" {...props}></Icon>
