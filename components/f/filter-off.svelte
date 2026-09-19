<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0hf1wm2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0hf1wm2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:filter-off" {...props}></Icon>
