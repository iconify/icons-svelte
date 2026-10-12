<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frd-8-btx.css';
import '../../css/p/p9big2yaj.css';
import '../../css/u/uir1vq-bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="frd-8-btx"/><path class="p9big2yaj"/><path class="uir1vq-bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-lock-48-bold" {...props}></Icon>
