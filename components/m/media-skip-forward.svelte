<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izdt5_wln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="izdt5_wln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-skip-forward" {...props}></Icon>
