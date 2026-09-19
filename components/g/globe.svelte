<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udy9dlbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="udy9dlbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:globe" {...props}></Icon>
