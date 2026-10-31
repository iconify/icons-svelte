<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkvl1_a7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkvl1_a7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-archive-gloss" {...props}></Icon>
