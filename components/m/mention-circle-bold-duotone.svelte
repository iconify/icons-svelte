<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/h/h3ssicb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path clip-rule="evenodd" class="h3ssicb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mention-circle-bold-duotone" {...props}></Icon>
