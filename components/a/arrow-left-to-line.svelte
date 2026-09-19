<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl2u2mtnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fl2u2mtnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-left-to-line" {...props}></Icon>
