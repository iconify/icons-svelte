<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhr-rwbyo.css';
import '../../css/d/d3xearisc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhr-rwbyo"/><path class="d3xearisc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:barn" {...props}></Icon>
