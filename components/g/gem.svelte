<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi4esybmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yi4esybmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gem" {...props}></Icon>
