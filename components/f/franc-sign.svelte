<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te59bx3dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="te59bx3dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:franc-sign" {...props}></Icon>
