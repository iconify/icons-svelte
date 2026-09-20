<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb13_846r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb13_846r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-g-circle" {...props}></Icon>
