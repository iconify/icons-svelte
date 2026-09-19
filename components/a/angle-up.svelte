<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6syj6bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p6syj6bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angle-up" {...props}></Icon>
