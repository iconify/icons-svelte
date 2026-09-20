<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cltl31bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cltl31bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-pie-3-filled" {...props}></Icon>
