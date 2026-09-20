<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3h-12bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3h-12bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fullscreen-1" {...props}></Icon>
