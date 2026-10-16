<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xquc5jbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xquc5jbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crankshaft-20-bold" {...props}></Icon>
