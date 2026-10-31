<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfzn5_bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfzn5_bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-progress-quarter-fill-round" {...props}></Icon>
