<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8vld8bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8vld8bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bike-pedal-mountain" {...props}></Icon>
