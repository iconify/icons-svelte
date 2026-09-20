<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-hxbz97p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-hxbz97p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-half-2-filled" {...props}></Icon>
