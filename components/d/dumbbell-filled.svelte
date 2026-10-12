<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j13j-opwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j13j-opwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dumbbell-filled" {...props}></Icon>
