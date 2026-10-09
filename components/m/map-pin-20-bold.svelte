<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0kzgmg_q.css';
import '../../css/o/o4zy8hb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e0kzgmg_q"/><path class="o4zy8hb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-20-bold" {...props}></Icon>
