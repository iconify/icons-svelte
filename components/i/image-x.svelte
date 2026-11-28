<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl389c8af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl389c8af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-x" {...props}></Icon>
