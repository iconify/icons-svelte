<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sroc94bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sroc94bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-left-from-line" {...props}></Icon>
