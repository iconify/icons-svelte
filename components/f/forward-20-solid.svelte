<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfrv9c1za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yfrv9c1za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:forward-20-solid" {...props}></Icon>
