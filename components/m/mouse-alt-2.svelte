<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgoclccam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgoclccam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mouse-alt-2" {...props}></Icon>
