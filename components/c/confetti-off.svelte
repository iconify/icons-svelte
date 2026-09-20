<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed0ui5bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed0ui5bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:confetti-off" {...props}></Icon>
