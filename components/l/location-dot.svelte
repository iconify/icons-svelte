<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz6siedjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="sz6siedjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:location-dot" {...props}></Icon>
