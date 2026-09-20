<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0-2jsc-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0-2jsc-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-sync" {...props}></Icon>
