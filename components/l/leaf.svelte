<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhe9yd_sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zhe9yd_sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:leaf" {...props}></Icon>
