<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c98kmzb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c98kmzb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:drumstick-bite" {...props}></Icon>
