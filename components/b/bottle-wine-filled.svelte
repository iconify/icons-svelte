<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn3ycljxj.css';
import '../../css/l/lfs1rybvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn3ycljxj"/><path class="lfs1rybvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bottle-wine-filled" {...props}></Icon>
