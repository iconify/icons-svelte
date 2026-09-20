<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1x5hz-hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1x5hz-hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-up-long-line" {...props}></Icon>
