<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqi-weisu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":384};
const content = `<path class="uqi-weisu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:play" {...props}></Icon>
