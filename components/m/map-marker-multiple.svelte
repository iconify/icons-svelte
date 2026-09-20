<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dizyogbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dizyogbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-multiple" {...props}></Icon>
