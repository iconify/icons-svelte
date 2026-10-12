<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t664lpb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t664lpb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clock-8-filled" {...props}></Icon>
