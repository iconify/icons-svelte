<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adqshw3kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adqshw3kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:protocol" {...props}></Icon>
