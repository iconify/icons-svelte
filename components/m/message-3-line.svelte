<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vczk4db9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vczk4db9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-3-line" {...props}></Icon>
