<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp6tc4bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lp6tc4bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-left-stipple" {...props}></Icon>
