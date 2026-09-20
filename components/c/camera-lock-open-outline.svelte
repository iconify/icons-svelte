<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lges67bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lges67bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-lock-open-outline" {...props}></Icon>
