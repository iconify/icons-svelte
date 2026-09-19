<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqqjq7o-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cqqjq7o-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chart-pie" {...props}></Icon>
