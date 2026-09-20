<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvi3j2b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uvi3j2b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:map-marker" {...props}></Icon>
