<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d57uaiwla.css';
import '../../css/w/wtnptnb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d57uaiwla"/><path class="wtnptnb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:door" {...props}></Icon>
