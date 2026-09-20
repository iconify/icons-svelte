<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7gyohbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7gyohbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rectangle" {...props}></Icon>
