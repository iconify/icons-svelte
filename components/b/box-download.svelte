<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2q9le6mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2q9le6mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-download" {...props}></Icon>
