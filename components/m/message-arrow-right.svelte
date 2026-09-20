<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1rc55bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1rc55bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-arrow-right" {...props}></Icon>
