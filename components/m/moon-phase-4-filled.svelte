<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1y50gb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1y50gb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-4-filled" {...props}></Icon>
