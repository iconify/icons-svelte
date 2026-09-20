<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxysq13ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxysq13ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-off" {...props}></Icon>
