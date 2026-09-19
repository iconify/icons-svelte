<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa17g_wlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="wa17g_wlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:film" {...props}></Icon>
