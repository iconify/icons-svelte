<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-0l9b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-0l9b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cursor-default-click-outline" {...props}></Icon>
