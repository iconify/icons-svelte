<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgooogbsq.css';
import '../../css/d/d0-_7mw1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgooogbsq"/><path class="d0-_7mw1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pizza-filled" {...props}></Icon>
