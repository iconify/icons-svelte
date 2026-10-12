<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4g99_bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4g99_bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:alarm-clock-off-filled" {...props}></Icon>
