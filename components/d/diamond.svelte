<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdyeyv2or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fdyeyv2or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:diamond" {...props}></Icon>
