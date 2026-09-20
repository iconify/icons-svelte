<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_bezuhgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_bezuhgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-neutral" {...props}></Icon>
