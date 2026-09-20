<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl69xg8ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl69xg8ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left-2-filled" {...props}></Icon>
