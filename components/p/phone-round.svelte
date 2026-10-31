<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs_grrb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs_grrb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:phone-round" {...props}></Icon>
