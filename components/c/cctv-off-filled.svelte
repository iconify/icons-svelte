<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_nt-ijv.css';
import '../../css/n/nwez_dbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in_nt-ijv"/><path class="nwez_dbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cctv-off-filled" {...props}></Icon>
