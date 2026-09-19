<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa0h4yvth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b fa0h4yvth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chair" {...props}></Icon>
