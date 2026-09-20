<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6tj6cbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6tj6cbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:2fauth-light" {...props}></Icon>
