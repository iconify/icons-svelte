<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew969ac-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ew969ac-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ingestion-report" {...props}></Icon>
