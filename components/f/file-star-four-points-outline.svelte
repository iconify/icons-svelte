<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um2ox6b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um2ox6b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-star-four-points-outline" {...props}></Icon>
