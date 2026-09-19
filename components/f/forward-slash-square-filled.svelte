<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw1zb91cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw1zb91cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:forward-slash-square-filled" {...props}></Icon>
