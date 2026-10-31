<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzydt9bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzydt9bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:loader-circle-gloss" {...props}></Icon>
