<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uycdujbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="uycdujbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:r-square" {...props}></Icon>
