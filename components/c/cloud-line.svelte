<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2_a0kb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2_a0kb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cloud-line" {...props}></Icon>
