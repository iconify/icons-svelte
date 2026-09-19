<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6dd5bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hn6dd5bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:jsfiddle" {...props}></Icon>
