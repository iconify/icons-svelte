<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flc299r4o.css';
import '../../css/s/sy2gigbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flc299r4o"/><path class="sy2gigbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:add-folder-bold-duotone" {...props}></Icon>
