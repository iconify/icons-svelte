<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7gj44blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<path class="g7gj44blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:flame" {...props}></Icon>
