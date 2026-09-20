<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riu_o1bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="riu_o1bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:credit-card" {...props}></Icon>
