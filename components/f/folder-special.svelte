<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puuzwgb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="puuzwgb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:folder-special" {...props}></Icon>
