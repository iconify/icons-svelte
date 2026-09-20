<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4cepmb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4cepmb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:panorama-vertical-outline" {...props}></Icon>
