<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqaj9fbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqaj9fbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:half-moon" {...props}></Icon>
