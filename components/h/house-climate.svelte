<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e259y2b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e259y2b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-climate" {...props}></Icon>
