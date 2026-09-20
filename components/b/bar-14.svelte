<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jez7kwixy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jez7kwixy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:bar-14" {...props}></Icon>
