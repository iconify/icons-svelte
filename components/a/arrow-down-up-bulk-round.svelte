<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj3yo8bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj3yo8bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-up-bulk-round" {...props}></Icon>
