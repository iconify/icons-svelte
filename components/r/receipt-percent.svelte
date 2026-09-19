<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0661zwvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0661zwvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:receipt-percent" {...props}></Icon>
