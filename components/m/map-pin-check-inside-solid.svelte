<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj2genbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj2genbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-pin-check-inside-solid" {...props}></Icon>
