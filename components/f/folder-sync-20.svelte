<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3me-4caq.css';
import '../../css/k/kvxb8_bsg.css';
import '../../css/s/sii7hvb1q.css';
import '../../css/l/l1sf0vffp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="kvxb8_bsg"/><path class="sii7hvb1q"/><path class="l1sf0vffp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-sync-20" {...props}></Icon>
