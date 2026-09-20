<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub97n3bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub97n3bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-s-line" {...props}></Icon>
