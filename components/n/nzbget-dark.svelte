<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/del0unbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="del0unbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nzbget-dark" {...props}></Icon>
