<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1ebwl1ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ebwl1ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lightbulb-line" {...props}></Icon>
