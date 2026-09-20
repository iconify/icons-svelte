<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q23lrv8wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q23lrv8wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-outline" {...props}></Icon>
