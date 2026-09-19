<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chjiditfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chjiditfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-rocket" {...props}></Icon>
