<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub_swd5sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub_swd5sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:playlist-off" {...props}></Icon>
