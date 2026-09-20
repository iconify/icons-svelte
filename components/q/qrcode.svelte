<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djat35b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="djat35b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:qrcode" {...props}></Icon>
