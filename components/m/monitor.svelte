<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/romo1bcpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="romo1bcpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:monitor" {...props}></Icon>
