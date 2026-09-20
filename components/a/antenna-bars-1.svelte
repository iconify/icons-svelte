<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw4zrn_4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw4zrn_4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:antenna-bars-1" {...props}></Icon>
