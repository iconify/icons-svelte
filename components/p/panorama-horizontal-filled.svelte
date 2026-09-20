<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u05psrofy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u05psrofy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:panorama-horizontal-filled" {...props}></Icon>
