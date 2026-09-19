<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svg3_r69m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="svg3_r69m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:glass" {...props}></Icon>
