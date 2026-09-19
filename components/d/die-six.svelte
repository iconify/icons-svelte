<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3k8zedlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m3k8zedlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:die-six" {...props}></Icon>
