<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3cra4fap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3cra4fap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:diamond-ring-line" {...props}></Icon>
