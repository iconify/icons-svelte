<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npr66-bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npr66-bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:docment-fill" {...props}></Icon>
