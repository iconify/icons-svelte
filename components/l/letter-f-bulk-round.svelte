<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa6pubb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa6pubb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-f-bulk-round" {...props}></Icon>
