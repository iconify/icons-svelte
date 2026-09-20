<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf4ud-_ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zf4ud-_ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:quote-left" {...props}></Icon>
