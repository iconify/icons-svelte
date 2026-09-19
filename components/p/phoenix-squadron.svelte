<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4-77ibpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j4-77ibpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:phoenix-squadron" {...props}></Icon>
