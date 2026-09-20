<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9h-k4bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9h-k4bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:animation-outline" {...props}></Icon>
