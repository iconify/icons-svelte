<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfq142g3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfq142g3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-search-corner-round" {...props}></Icon>
