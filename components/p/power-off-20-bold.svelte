<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbfuulb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbfuulb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-off-20-bold" {...props}></Icon>
