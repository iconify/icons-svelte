<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sijxjfgam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sijxjfgam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pencil2" {...props}></Icon>
