<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo4ycbbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oo4ycbbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:biltema-dark" {...props}></Icon>
