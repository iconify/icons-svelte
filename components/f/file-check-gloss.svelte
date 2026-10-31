<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttvac-bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttvac-bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-check-gloss" {...props}></Icon>
