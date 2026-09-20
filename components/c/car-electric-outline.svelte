<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnam857uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnam857uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-electric-outline" {...props}></Icon>
