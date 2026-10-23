<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl1jl-bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl1jl-bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:baseline" {...props}></Icon>
