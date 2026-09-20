<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd1w7wl8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd1w7wl8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:broken-heart" {...props}></Icon>
