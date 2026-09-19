<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg6kdcc7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg6kdcc7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-handle" {...props}></Icon>
