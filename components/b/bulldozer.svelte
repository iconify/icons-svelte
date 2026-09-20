<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crs8b8bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crs8b8bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulldozer" {...props}></Icon>
