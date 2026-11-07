<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_frcb-c.css';
import '../../css/h/h3ssicb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path clip-rule="evenodd" class="h3ssicb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mention-square-bold-duotone" {...props}></Icon>
