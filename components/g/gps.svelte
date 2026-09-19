<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe0g7_blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe0g7_blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:gps" {...props}></Icon>
