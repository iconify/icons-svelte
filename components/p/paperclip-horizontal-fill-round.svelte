<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idr8lu39n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idr8lu39n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paperclip-horizontal-fill-round" {...props}></Icon>
