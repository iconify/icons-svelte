<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxzt4c83h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzt4c83h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:filter-line" {...props}></Icon>
