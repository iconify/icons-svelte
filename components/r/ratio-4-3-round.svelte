<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az_aflber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az_aflber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-4-3-round" {...props}></Icon>
