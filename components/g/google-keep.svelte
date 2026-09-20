<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfx72d7mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfx72d7mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-keep" {...props}></Icon>
