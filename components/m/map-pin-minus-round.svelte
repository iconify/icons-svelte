<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w99-s6t3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w99-s6t3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-minus-round" {...props}></Icon>
