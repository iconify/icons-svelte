<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy87cfkhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vy87cfkhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:copyright" {...props}></Icon>
