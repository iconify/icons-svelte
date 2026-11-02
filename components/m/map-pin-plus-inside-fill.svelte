<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la7fppbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la7fppbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-plus-inside-fill" {...props}></Icon>
