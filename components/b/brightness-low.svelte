<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaj2zoj2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaj2zoj2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brightness-low" {...props}></Icon>
