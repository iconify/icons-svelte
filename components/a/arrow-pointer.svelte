<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfd4fdc5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="wfd4fdc5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-pointer" {...props}></Icon>
