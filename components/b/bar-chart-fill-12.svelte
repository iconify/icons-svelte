<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py5kzrbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="py5kzrbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-fill-12" {...props}></Icon>
