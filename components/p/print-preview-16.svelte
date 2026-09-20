<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha_hsdf3i.css';
import '../../css/z/zfb6-85zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ha_hsdf3i"/><path clip-rule="evenodd" class="zfb6-85zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:print-preview-16" {...props}></Icon>
