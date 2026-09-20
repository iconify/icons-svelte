<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw13ow3ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw13ow3ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-auto" {...props}></Icon>
