<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyu1pxbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyu1pxbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-progress-three-quarter-round" {...props}></Icon>
