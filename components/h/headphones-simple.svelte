<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc1s4iqke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yc1s4iqke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:headphones-simple" {...props}></Icon>
