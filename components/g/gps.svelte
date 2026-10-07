<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngg5mbc4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngg5mbc4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:gps" {...props}></Icon>
