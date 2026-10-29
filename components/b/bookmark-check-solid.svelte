<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp_gg1bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp_gg1bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-check-solid" {...props}></Icon>
