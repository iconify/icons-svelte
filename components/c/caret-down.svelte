<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy341l93m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gy341l93m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-down" {...props}></Icon>
