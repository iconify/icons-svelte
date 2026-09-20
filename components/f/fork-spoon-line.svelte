<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-7b-6vtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-7b-6vtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fork-spoon-line" {...props}></Icon>
