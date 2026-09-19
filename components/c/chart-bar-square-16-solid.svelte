<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt5jl0bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yt5jl0bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chart-bar-square-16-solid" {...props}></Icon>
