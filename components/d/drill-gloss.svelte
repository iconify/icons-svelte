<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihch-kbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihch-kbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drill-gloss" {...props}></Icon>
