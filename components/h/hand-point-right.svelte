<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8g6hdbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8g6hdbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-point-right" {...props}></Icon>
