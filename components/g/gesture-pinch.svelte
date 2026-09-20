<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l33nqq3_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l33nqq3_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gesture-pinch" {...props}></Icon>
