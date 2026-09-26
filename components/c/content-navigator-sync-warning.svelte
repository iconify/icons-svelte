<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flqsn-boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="flqsn-boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:content-navigator-sync-warning" {...props}></Icon>
