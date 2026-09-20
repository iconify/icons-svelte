<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl6_mcbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rl6_mcbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:girl" {...props}></Icon>
