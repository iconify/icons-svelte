<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl6o323gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jl6o323gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bottom-align-filled" {...props}></Icon>
