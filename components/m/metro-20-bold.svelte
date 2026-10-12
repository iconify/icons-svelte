<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz29xlien.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wz29xlien"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:metro-20-bold" {...props}></Icon>
