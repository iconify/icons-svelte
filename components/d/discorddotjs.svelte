<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu_x_zbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu_x_zbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:discorddotjs" {...props}></Icon>
