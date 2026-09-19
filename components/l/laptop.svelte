<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8_gtobak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y8_gtobak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:laptop" {...props}></Icon>
