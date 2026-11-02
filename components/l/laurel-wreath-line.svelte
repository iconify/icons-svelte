<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_pvnmonr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_pvnmonr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laurel-wreath-line" {...props}></Icon>
