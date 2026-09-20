<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxgp7eb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zxgp7eb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:location" {...props}></Icon>
