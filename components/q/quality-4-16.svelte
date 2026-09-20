<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh14dfj_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yh14dfj_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:quality-4-16" {...props}></Icon>
