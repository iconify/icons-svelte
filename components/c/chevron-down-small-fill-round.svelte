<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1biiwb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1biiwb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-small-fill-round" {...props}></Icon>
