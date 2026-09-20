<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz6upcgeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz6upcgeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:microsoft-loop-fill" {...props}></Icon>
