<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j798y7bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j798y7bdv primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-down-duotone" {...props}></Icon>
