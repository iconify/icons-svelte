<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zapfc8g7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zapfc8g7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-outline-filled" {...props}></Icon>
