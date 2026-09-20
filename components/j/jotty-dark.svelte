<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhjjvtbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhjjvtbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jotty-dark" {...props}></Icon>
