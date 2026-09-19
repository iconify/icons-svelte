<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y360en5ri.css';
import '../../css/i/if80w2ton.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y360en5ri"/><path class="if80w2ton"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-stroke-circle-half" {...props}></Icon>
