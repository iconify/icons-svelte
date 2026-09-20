<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wih5c8o4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wih5c8o4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-right-horizontal-stipple-up" {...props}></Icon>
