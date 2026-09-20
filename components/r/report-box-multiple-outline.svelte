<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suireybjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suireybjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:report-box-multiple-outline" {...props}></Icon>
