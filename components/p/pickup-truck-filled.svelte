<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utcr3yxbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utcr3yxbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pickup-truck-filled" {...props}></Icon>
