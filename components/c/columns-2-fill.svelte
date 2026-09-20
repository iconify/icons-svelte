<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnw_gdc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnw_gdc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-2-fill" {...props}></Icon>
