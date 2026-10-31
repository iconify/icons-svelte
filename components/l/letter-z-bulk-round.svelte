<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8vghd45x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8vghd45x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-z-bulk-round" {...props}></Icon>
