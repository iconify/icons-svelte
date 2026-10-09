<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxkzprb8a.css';
import '../../css/l/lscshqmdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gxkzprb8a"/><path class="lscshqmdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-snow-20" {...props}></Icon>
