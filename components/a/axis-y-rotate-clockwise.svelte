<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suw_391zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suw_391zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-y-rotate-clockwise" {...props}></Icon>
