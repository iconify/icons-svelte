<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvoe02p8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvoe02p8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-wash" {...props}></Icon>
