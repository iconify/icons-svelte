<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af4-9ib1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="af4-9ib1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-flag" {...props}></Icon>
