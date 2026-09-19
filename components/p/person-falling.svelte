<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf40h41pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xf40h41pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-falling" {...props}></Icon>
