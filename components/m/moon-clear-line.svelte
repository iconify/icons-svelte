<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvyb5zf-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvyb5zf-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:moon-clear-line" {...props}></Icon>
