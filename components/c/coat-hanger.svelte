<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l64_-xbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l64_-xbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coat-hanger" {...props}></Icon>
