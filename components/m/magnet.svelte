<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfrb4p-aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jfrb4p-aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:magnet" {...props}></Icon>
