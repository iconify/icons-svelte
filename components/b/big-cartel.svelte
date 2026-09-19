<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l73vfmbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l73vfmbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:big-cartel" {...props}></Icon>
