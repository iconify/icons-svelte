<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdedo1bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdedo1bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-eye-outline" {...props}></Icon>
