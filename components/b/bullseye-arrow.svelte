<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bolsvf0ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bolsvf0ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bullseye-arrow" {...props}></Icon>
