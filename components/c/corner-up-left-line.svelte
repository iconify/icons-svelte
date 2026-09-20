<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmin66b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmin66b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-up-left-line" {...props}></Icon>
