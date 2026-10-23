<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7wms___w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7wms___w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-axis-3d" {...props}></Icon>
