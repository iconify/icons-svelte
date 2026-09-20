<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl43-irdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl43-irdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-dollar-filled" {...props}></Icon>
