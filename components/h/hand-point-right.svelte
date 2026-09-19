<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ss5zbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5ss5zbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-point-right" {...props}></Icon>
