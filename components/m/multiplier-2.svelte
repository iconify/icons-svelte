<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki3taftaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="ki3taftaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:multiplier-2" {...props}></Icon>
