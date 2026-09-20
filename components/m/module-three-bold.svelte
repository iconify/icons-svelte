<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryf61ccyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryf61ccyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:module-three-bold" {...props}></Icon>
