<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-5-ltbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-5-ltbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-home" {...props}></Icon>
