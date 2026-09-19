<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovc8f6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ovc8f6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:left-arrow" {...props}></Icon>
