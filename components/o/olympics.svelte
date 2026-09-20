<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi0g1gbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi0g1gbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:olympics" {...props}></Icon>
