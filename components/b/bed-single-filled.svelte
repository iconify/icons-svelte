<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_9v2_b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_9v2_b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bed-single-filled" {...props}></Icon>
