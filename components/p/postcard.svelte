<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moygi0x4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moygi0x4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:postcard" {...props}></Icon>
