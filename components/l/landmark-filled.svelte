<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e77eg_m-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e77eg_m-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:landmark-filled" {...props}></Icon>
