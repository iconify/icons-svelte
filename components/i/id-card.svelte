<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9wtks1km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2112,"height":1568};
const content = `<path class="e9wtks1km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:id-card" {...props}></Icon>
