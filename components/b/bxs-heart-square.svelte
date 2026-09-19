<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xecjju-9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xecjju-9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-heart-square" {...props}></Icon>
