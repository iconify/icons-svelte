<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhket8_zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zhket8_zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bore-hole" {...props}></Icon>
