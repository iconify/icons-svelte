<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr1_dtboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kr1_dtboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:o" {...props}></Icon>
