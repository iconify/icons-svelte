<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud354hdiy.css';
import '../../css/f/fdn9dkb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ud354hdiy"/><path class="fdn9dkb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brain-20-bold" {...props}></Icon>
