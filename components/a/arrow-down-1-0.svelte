<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp-d-98ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp-d-98ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-1-0" {...props}></Icon>
