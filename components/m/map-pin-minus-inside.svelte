<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ub34b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ub34b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-pin-minus-inside" {...props}></Icon>
