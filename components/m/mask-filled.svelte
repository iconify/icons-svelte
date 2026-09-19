<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqog2_b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqog2_b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mask-filled" {...props}></Icon>
