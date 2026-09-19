<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpqxus1cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="rpqxus1cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:camera-rotate" {...props}></Icon>
