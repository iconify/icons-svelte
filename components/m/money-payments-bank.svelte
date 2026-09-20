<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_qnxmbps.css';
import '../../css/n/np6k2ybks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e_qnxmbps"/><path class="np6k2ybks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-bank" {...props}></Icon>
