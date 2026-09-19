<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq1z-kbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cq1z-kbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:info-circle" {...props}></Icon>
