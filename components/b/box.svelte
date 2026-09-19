<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot_iz2bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1000};
const content = `<path class="ot_iz2bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:box" {...props}></Icon>
