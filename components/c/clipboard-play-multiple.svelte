<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdum7db5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdum7db5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-play-multiple" {...props}></Icon>
