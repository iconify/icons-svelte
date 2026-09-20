<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1_q279fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1_q279fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:aed-line" {...props}></Icon>
