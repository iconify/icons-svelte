<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq8zhvb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq8zhvb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cube-filled" {...props}></Icon>
