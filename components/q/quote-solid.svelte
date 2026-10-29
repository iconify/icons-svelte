<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1onb6bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1onb6bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:quote-solid" {...props}></Icon>
