<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4c7fub3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4c7fub3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-c-diamond-solid" {...props}></Icon>
