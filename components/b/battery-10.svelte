<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1p0d4jsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1p0d4jsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-10" {...props}></Icon>
