<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzlg-u0et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzlg-u0et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-off" {...props}></Icon>
