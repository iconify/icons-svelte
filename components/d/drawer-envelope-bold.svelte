<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgalthvnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgalthvnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:drawer-envelope-bold" {...props}></Icon>
