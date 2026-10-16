<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9z4m6_0r.css';
import '../../css/j/j1jrbccvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<path class="j9z4m6_0r"/><path class="j1jrbccvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flame" {...props}></Icon>
