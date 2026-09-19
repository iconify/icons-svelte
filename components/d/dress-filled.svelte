<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8si_wb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8si_wb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dress-filled" {...props}></Icon>
