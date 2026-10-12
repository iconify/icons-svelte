<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_vsq7l3i.css';
import '../../css/e/edyk28bgn.css';
import '../../css/i/i09p7lbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="edyk28bgn"/><path class="i09p7lbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-x-filled" {...props}></Icon>
