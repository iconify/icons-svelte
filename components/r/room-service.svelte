<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_z8_tzny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_z8_tzny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:room-service" {...props}></Icon>
