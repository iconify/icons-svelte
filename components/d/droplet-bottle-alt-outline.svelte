<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dub6k1bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dub6k1bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:droplet-bottle-alt-outline" {...props}></Icon>
