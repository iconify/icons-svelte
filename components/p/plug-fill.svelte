<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap2f_x_-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap2f_x_-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:plug-fill" {...props}></Icon>
