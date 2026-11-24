<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfr8ahb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfr8ahb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dumbbell-filled" {...props}></Icon>
