<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhaiv-07w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhaiv-07w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-key" {...props}></Icon>
