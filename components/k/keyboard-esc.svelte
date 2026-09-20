<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gis85s77z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gis85s77z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-esc" {...props}></Icon>
