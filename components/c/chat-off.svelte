<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gahn8ob2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gahn8ob2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-off" {...props}></Icon>
