<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk7zhccdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk7zhccdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-music-outline" {...props}></Icon>
