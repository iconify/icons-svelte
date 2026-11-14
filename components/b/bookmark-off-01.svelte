<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li4uwhbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li4uwhbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-off-01" {...props}></Icon>
