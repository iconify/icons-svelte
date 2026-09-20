<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_jgs3bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_jgs3bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-cruise-control" {...props}></Icon>
