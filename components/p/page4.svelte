<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x09a6eefl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x09a6eefl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:page4" {...props}></Icon>
