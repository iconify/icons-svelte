<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx6l9tbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wx6l9tbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:box" {...props}></Icon>
