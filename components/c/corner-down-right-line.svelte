<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toyuwjkjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toyuwjkjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-down-right-line" {...props}></Icon>
