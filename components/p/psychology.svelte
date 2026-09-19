<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktxbgbbpn.css';
import '../../css/g/g_4d4-bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktxbgbbpn"/><path class="g_4d4-bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:psychology" {...props}></Icon>
