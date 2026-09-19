<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrrzcn2dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vrrzcn2dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:brazilian-real-sign" {...props}></Icon>
