<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly-_et2sc.css';
import '../../css/x/xp5j9_8ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-_et2sc"/><path class="xp5j9_8ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-chat-bold-duotone" {...props}></Icon>
