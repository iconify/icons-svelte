<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j10_t9shp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j10_t9shp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-spark" {...props}></Icon>
