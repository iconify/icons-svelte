<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8-f5abwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8-f5abwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-pin-plus-inside-solid" {...props}></Icon>
