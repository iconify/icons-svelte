<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd48edbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd48edbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dual-sim-2-line" {...props}></Icon>
