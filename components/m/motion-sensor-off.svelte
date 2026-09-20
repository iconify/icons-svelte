<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z32lg_tbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z32lg_tbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:motion-sensor-off" {...props}></Icon>
