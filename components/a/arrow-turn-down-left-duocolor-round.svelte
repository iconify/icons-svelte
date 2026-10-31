<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0qnszbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0qnszbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-down-left-duocolor-round" {...props}></Icon>
