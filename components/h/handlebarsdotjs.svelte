<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl5cxwvuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl5cxwvuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:handlebarsdotjs" {...props}></Icon>
