<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc33240jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc33240jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-horizontal-fill-round" {...props}></Icon>
