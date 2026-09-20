<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3esgbc0q.css';
import '../../css/z/zy8g_6utu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3esgbc0q"/><path class="zy8g_6utu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kagi" {...props}></Icon>
