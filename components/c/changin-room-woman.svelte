<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiuc4wwhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiuc4wwhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:changin-room-woman" {...props}></Icon>
