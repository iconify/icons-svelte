<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq7wclblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq7wclblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-bubble-filled" {...props}></Icon>
