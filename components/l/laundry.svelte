<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa-2tbcpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="wa-2tbcpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:laundry" {...props}></Icon>
