<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz412mbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz412mbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-down-circle" {...props}></Icon>
