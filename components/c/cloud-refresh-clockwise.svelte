<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro5b2tlle.css';
import '../../css/f/f-vbie9xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro5b2tlle"/><path class="f-vbie9xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-refresh-clockwise" {...props}></Icon>
