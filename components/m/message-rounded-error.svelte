<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnx-vib2x.css';
import '../../css/k/k4r099b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnx-vib2x"/><path class="k4r099b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-rounded-error" {...props}></Icon>
