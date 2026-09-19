<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6fpu11wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x6fpu11wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-double-left" {...props}></Icon>
