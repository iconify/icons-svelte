<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2sj9mb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w2sj9mb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:eject" {...props}></Icon>
