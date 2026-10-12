<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtq1wfort.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtq1wfort"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:music-2-filled" {...props}></Icon>
