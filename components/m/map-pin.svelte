<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0lbkabqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="y0lbkabqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:map-pin" {...props}></Icon>
