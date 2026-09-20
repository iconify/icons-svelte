<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm7-k-41s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm7-k-41s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gamepad-1-filled" {...props}></Icon>
