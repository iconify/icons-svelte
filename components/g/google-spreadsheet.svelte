<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_m-qtr0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_m-qtr0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-spreadsheet" {...props}></Icon>
