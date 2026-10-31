<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2rlf7fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co2rlf7fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bold-duotone-round" {...props}></Icon>
