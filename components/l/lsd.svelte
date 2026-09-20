<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfu7vx_iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfu7vx_iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lsd" {...props}></Icon>
