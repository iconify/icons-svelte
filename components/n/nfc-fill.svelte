<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_xfgm5op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_xfgm5op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:nfc-fill" {...props}></Icon>
