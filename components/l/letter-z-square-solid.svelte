<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtvkwwb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvkwwb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-z-square-solid" {...props}></Icon>
