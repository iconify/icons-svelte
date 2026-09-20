<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8qh5424e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8qh5424e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:one-hexagon-solid" {...props}></Icon>
