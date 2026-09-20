<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmp74nh4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dmp74nh4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:loop-circular" {...props}></Icon>
