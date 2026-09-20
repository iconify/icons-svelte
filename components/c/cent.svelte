<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm20vx1_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm20vx1_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cent" {...props}></Icon>
