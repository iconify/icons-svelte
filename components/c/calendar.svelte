<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oefg2-ghd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oefg2-ghd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:calendar" {...props}></Icon>
