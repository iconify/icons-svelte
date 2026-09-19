<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9ifqu2ej.css';
import '../../css/y/yh79mabjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9ifqu2ej"/><path class="yh79mabjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:archive-arrow-down" {...props}></Icon>
