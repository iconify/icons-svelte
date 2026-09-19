<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmkzlybnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmkzlybnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:edge-legacy" {...props}></Icon>
