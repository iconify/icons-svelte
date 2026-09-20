<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdtr5e43k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fdtr5e43k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-geor-man" {...props}></Icon>
