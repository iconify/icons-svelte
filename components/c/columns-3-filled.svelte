<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbm0q3_fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbm0q3_fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:columns-3-filled" {...props}></Icon>
