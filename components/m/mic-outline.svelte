<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnkgvjblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":416};
const content = `<path class="qnkgvjblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mic-outline" {...props}></Icon>
