<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxl72eb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxl72eb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:borgbackup" {...props}></Icon>
