<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_oqib-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_oqib-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-stroke-circle-filled" {...props}></Icon>
