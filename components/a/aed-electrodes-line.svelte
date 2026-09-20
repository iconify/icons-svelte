<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejx6idb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejx6idb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:aed-electrodes-line" {...props}></Icon>
