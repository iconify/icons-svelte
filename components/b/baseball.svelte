<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4n-w4qjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w4n-w4qjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:baseball" {...props}></Icon>
