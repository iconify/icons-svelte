<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq6tdnpts.css';
import '../../css/t/t3di-p3xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="sq6tdnpts"/><path class="t3di-p3xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:morocco" {...props}></Icon>
