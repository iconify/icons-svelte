<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egjbv50hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egjbv50hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-flow" {...props}></Icon>
