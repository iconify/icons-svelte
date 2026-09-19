<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xto2pgbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xto2pgbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arrows-vert" {...props}></Icon>
