<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0n2bubor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d0n2bubor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infinity-20-bold" {...props}></Icon>
