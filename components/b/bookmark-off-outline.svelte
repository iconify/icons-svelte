<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbsk9kbsr.css';
import '../../css/i/ionjprbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbsk9kbsr"/><path class="ionjprbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-off-outline" {...props}></Icon>
