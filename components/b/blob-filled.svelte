<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrq_v6q4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrq_v6q4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:blob-filled" {...props}></Icon>
