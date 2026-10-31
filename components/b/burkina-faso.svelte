<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx_xvr4ug.css';
import '../../css/y/y70x02bra.css';
import '../../css/l/lmzttacpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wx_xvr4ug"/><path class="y70x02bra"/><path class="lmzttacpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:burkina-faso" {...props}></Icon>
