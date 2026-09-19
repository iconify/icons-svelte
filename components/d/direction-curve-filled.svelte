<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo-i9d5nt.css';
import '../../css/g/g5gysrbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bo-i9d5nt"/><path class="g5gysrbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-curve-filled" {...props}></Icon>
