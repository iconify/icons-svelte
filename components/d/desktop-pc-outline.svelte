<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btw2aqb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btw2aqb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:desktop-pc-outline" {...props}></Icon>
