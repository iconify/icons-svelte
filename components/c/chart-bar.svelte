<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t114_gb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t114_gb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chart-bar" {...props}></Icon>
