<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_n5p1bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_n5p1bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:brick-wall" {...props}></Icon>
