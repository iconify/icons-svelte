<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1g4vx_wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1g4vx_wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-left" {...props}></Icon>
