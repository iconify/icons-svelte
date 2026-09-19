<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj4ta2cbo.css';
import '../../css/t/t4yq35mvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yj4ta2cbo"/><path class="t4yq35mvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-star-filled" {...props}></Icon>
