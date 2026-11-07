<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seb4uo8hr.css';
import '../../css/b/b03wwil3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="seb4uo8hr"/><path class="b03wwil3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-check-minimalistic-bold-duotone" {...props}></Icon>
