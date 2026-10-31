<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfyge_n8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfyge_n8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-alt-bulk-round" {...props}></Icon>
