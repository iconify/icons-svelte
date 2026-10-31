<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srjdv2b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srjdv2b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:raccoon-round" {...props}></Icon>
