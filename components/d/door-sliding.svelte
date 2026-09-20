<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us55ghb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us55ghb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:door-sliding" {...props}></Icon>
