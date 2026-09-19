<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_bvvacrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="w_bvvacrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:favorite" {...props}></Icon>
