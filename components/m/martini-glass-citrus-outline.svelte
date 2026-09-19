<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcx_w8b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcx_w8b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:martini-glass-citrus-outline" {...props}></Icon>
