<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thrm-bbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thrm-bbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-moon-filled" {...props}></Icon>
