<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar1m2gsxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1m2gsxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compare-horizontal" {...props}></Icon>
