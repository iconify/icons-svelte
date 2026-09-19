<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oebu9o-lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oebu9o-lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:flag" {...props}></Icon>
