<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aebd-tbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aebd-tbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-off-outline" {...props}></Icon>
