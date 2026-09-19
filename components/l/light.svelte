<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xksqnnbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xksqnnbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:light" {...props}></Icon>
