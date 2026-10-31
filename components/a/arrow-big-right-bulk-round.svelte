<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c68udouje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c68udouje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-big-right-bulk-round" {...props}></Icon>
