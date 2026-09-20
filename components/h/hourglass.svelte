<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2908egb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij2908egb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:hourglass" {...props}></Icon>
