<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbs36hbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbs36hbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gamepad-directional-filled" {...props}></Icon>
