<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v93gcqgfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v93gcqgfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:electric-wheelchair" {...props}></Icon>
