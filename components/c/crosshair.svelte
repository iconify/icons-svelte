<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih1th_vdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih1th_vdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:crosshair" {...props}></Icon>
