<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7xm-fxfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x7xm-fxfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:bell" {...props}></Icon>
