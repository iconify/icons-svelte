<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y40y2nbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y40y2nbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:desk-lamp-off" {...props}></Icon>
