<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if7dj2d5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if7dj2d5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bluetooth-disabled" {...props}></Icon>
