<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4w5y8boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4w5y8boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-double-decker" {...props}></Icon>
