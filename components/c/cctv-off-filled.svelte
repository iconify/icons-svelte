<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt5pu7wpk.css';
import '../../css/n/nwez_dbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt5pu7wpk"/><path class="nwez_dbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cctv-off-filled" {...props}></Icon>
