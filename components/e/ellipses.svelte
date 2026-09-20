<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syoe0rb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="syoe0rb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:ellipses" {...props}></Icon>
