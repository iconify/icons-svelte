<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh6vd3p4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yh6vd3p4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ngc" {...props}></Icon>
