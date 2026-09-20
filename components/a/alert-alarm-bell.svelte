<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co17elbuu.css';
import '../../css/o/oh7_w2b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co17elbuu"/><path class="oh7_w2b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:alert-alarm-bell" {...props}></Icon>
