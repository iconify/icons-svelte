<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4ixj7sah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4ixj7sah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-bulk-round" {...props}></Icon>
