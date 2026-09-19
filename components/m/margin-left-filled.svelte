<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl69qz8ca.css';
import '../../css/b/b5aw_lbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl69qz8ca"/><rect class="b5aw_lbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:margin-left-filled" {...props}></Icon>
