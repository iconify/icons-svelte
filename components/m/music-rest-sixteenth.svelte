<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqlgjykdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqlgjykdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-rest-sixteenth" {...props}></Icon>
