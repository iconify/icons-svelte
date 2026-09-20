<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlwgpbcjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwgpbcjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dvd" {...props}></Icon>
