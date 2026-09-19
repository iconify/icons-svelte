<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfy3efzhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tfy3efzhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:load-balancer-local" {...props}></Icon>
