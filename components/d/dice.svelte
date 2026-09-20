<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdsl8pbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jdsl8pbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dice" {...props}></Icon>
