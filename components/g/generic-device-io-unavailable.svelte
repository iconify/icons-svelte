<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtk5ue39c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtk5ue39c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-io-unavailable" {...props}></Icon>
