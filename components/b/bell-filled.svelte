<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzyvu_nxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzyvu_nxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-filled" {...props}></Icon>
