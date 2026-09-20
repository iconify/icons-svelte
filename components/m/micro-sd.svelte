<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nny19uaef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nny19uaef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:micro-sd" {...props}></Icon>
