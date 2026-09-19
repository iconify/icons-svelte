<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3xearisc.css';
import '../../css/g/ga3pmjrdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3xearisc"/><path class="ga3pmjrdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:florist" {...props}></Icon>
