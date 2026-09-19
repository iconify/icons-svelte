<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st_46oxgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="st_46oxgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bubbles" {...props}></Icon>
