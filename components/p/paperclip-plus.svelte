<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3oq2shun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3oq2shun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paperclip-plus" {...props}></Icon>
