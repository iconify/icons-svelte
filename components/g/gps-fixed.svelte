<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyhdj7bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyhdj7bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gps-fixed" {...props}></Icon>
