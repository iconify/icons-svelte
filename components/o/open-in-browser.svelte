<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mum3xruae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mum3xruae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:open-in-browser" {...props}></Icon>
