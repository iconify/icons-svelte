<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntb91h_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wntb91h_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:electricity" {...props}></Icon>
