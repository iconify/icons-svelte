<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe2u2sqvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe2u2sqvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:calendar" {...props}></Icon>
