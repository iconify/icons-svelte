<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3zptuyzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="f3zptuyzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bed-pulse" {...props}></Icon>
