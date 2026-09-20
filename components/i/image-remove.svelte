<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf8zpjbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf8zpjbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-remove" {...props}></Icon>
