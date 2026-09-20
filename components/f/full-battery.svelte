<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6h4-2b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h6h4-2b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:full-battery" {...props}></Icon>
