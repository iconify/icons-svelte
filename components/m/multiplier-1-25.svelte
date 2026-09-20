<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji-p01brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="ji-p01brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:multiplier-1-25" {...props}></Icon>
