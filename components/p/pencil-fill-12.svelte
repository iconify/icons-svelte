<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4_9pb1zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k4_9pb1zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-fill-12" {...props}></Icon>
