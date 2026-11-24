<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7-n71b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7-n71b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:landmark-filled" {...props}></Icon>
