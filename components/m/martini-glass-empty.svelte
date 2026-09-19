<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4md5kkgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4md5kkgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:martini-glass-empty" {...props}></Icon>
