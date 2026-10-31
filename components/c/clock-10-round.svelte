<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy525o-xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy525o-xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-10-round" {...props}></Icon>
