<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7s6ofb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7s6ofb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:droplet" {...props}></Icon>
