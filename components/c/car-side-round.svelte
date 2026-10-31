<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yioqpyb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yioqpyb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:car-side-round" {...props}></Icon>
