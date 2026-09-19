<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-g__d1hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-g__d1hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:glass-martini" {...props}></Icon>
