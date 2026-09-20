<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoir4ebcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yoir4ebcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pluton" {...props}></Icon>
