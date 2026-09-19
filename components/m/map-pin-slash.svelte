<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn9u4w0zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hn9u4w0zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:map-pin-slash" {...props}></Icon>
