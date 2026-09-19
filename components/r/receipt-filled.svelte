<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi9t0_byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi9t0_byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:receipt-filled" {...props}></Icon>
