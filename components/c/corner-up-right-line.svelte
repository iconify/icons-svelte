<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxgevzonk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxgevzonk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-up-right-line" {...props}></Icon>
