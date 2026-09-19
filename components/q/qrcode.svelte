<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg9u1fbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zg9u1fbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:qrcode" {...props}></Icon>
