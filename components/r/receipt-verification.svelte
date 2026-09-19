<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk8zi3b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zk8zi3b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:receipt-verification" {...props}></Icon>
