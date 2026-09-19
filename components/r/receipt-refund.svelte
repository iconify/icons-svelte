<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytj0k685m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytj0k685m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:receipt-refund" {...props}></Icon>
