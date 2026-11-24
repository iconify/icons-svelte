<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg9whrtft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg9whrtft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:arrow-big-up-filled" {...props}></Icon>
