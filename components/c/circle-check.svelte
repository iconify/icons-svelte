<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdqndbb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qdqndbb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:circle-check" {...props}></Icon>
