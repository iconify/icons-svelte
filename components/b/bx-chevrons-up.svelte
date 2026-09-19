<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkpiz7yuq.css';
import '../../css/x/xh52_lwgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkpiz7yuq"/><path class="xh52_lwgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-chevrons-up" {...props}></Icon>
