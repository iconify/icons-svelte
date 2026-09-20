<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rof8sct4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rof8sct4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ripple-down" {...props}></Icon>
