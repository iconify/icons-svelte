<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twhm25guv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twhm25guv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-vertical-space-between" {...props}></Icon>
