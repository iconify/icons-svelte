<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g11id0skg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g11id0skg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-filled" {...props}></Icon>
