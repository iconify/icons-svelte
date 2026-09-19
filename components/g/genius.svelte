<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4-7j5d3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p4-7j5d3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:genius" {...props}></Icon>
