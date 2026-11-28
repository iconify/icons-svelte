<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb_vzo39h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_vzo39h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-video-check" {...props}></Icon>
