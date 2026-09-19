<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgs0fsb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="wgs0fsb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:image" {...props}></Icon>
