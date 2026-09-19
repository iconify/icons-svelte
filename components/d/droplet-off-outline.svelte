<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyy3pubza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyy3pubza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:droplet-off-outline" {...props}></Icon>
