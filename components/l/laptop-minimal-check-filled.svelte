<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir-kh0dyx.css';
import '../../css/v/vo8y2ebke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir-kh0dyx"/><path clip-rule="evenodd" class="vo8y2ebke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:laptop-minimal-check-filled" {...props}></Icon>
