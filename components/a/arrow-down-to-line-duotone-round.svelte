<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll1oe2bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll1oe2bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-to-line-duotone-round" {...props}></Icon>
