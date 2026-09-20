<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd1cm_bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yd1cm_bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:door" {...props}></Icon>
